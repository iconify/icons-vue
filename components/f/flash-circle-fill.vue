<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqy-tacas.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqy-tacas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flash-circle-fill" /></template>
