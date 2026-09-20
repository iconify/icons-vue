<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-4r5ndkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-4r5ndkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:expchain" /></template>
