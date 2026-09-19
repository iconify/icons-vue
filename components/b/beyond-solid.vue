<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozfan2bwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozfan2bwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:beyond-solid" /></template>
