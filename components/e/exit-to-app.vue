<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdfzsyblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdfzsyblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:exit-to-app" /></template>
