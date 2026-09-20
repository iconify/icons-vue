<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xief-cxdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xief-cxdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:css3-simple" /></template>
