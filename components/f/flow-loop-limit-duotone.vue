<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6-ylwfiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary z6-ylwfiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-loop-limit-duotone" /></template>
