<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9f5bpedd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9f5bpedd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-circle-fill" /></template>
