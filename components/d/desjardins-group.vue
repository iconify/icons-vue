<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snt92zbyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="snt92zbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:desjardins-group" /></template>
