<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc_gv2b1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yc_gv2b1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:elevator" /></template>
