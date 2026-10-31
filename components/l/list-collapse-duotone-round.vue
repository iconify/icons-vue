<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqcf44yln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xqcf44yln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-collapse-duotone-round" /></template>
