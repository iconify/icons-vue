<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lksd2czex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lksd2czex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cusd" /></template>
