<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw1l_zb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jw1l_zb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:check-all" /></template>
