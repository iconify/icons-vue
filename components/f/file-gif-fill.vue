<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pokm4jbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pokm4jbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:file-gif-fill" /></template>
