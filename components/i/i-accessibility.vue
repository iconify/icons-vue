<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd_v34b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hd_v34b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-accessibility" /></template>
