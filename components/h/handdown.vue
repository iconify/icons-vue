<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wrhom2bqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":704,"height":1024};
const content = `<path class="wrhom2bqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:handdown" /></template>
