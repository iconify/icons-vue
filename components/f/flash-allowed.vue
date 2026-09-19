<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izr1mgbxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izr1mgbxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:flash-allowed" /></template>
