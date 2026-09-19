<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6k78tbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q6k78tbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:database-nut-hex" /></template>
