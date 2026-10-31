<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmxb9zfvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmxb9zfvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:images-fill-round" /></template>
