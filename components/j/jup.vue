<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irduc8btt.css';
import '../../css/z/z1s3debyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irduc8btt"/><path class="z1s3debyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:jup" /></template>
