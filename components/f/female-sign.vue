<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i12ljv2bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i12ljv2bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:female-sign" /></template>
