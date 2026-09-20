<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1gl9ibjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1gl9ibjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-y-circle-solid" /></template>
