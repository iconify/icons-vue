<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztbl4bbma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ztbl4bbma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:align-right" /></template>
