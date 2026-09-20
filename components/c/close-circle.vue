<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd9y8ubqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9y8ubqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:close-circle" /></template>
