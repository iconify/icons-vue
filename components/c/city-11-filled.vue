<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siiur0snn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siiur0snn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-11-filled" /></template>
