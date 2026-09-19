<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq3j7uixf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":24};
const content = `<path class="xq3j7uixf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:asterisk" /></template>
