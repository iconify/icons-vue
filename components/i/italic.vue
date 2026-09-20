<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfylmybqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfylmybqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:italic" /></template>
