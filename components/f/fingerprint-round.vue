<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4t73obvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4t73obvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fingerprint-round" /></template>
