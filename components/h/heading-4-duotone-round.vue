<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsh2ghnfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsh2ghnfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heading-4-duotone-round" /></template>
