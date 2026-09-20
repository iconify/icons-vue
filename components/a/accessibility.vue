<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jziryxb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jziryxb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:accessibility" /></template>
