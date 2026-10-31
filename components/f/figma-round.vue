<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfa43gb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dfa43gb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:figma-round" /></template>
