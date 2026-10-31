<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhfc7cbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhfc7cbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="struq:arrow-left" /></template>
