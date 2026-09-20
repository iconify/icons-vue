<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/houoq25gr.css';
import '../../css/i/iidgtubnu.css';
import '../../css/s/su0illb2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="houoq25gr"/><path class="iidgtubnu"/><path class="su0illb2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:cloud-upload" /></template>
