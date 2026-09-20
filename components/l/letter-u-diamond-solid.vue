<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsx-s2bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gsx-s2bsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-u-diamond-solid" /></template>
