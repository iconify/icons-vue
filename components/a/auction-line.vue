<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mnv13yfyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnv13yfyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:auction-line" /></template>
