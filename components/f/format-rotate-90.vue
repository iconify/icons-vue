<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5w8bpbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5w8bpbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-rotate-90" /></template>
