<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j06qx_bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="j06qx_bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:hourglass4" /></template>
