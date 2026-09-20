<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyed-ac-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="qyed-ac-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:align-justify" /></template>
