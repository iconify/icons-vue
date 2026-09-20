<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/po936mb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po936mb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:fact-check-line" /></template>
