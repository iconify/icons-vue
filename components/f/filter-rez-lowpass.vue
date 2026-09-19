<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz2bgzbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jz2bgzbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:filter-rez-lowpass" /></template>
