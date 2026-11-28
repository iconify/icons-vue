<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnlc4esmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnlc4esmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:container-clock" /></template>
