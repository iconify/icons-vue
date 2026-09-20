<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjygv35-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wjygv35-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:florist-14" /></template>
