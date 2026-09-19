<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhb8habpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhb8habpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:jaguar" /></template>
