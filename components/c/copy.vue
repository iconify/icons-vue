<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu96an5_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iu96an5_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:copy" /></template>
