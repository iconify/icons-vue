<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckun01bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":29,"height":24};
const content = `<path class="ckun01bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:justify" /></template>
