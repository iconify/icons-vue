<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7dst5bos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7dst5bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:aliens-fill" /></template>
