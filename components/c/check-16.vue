<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkmo_cb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jkmo_cb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:check-16" /></template>
