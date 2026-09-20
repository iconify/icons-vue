<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-7y4g4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yx-7y4g4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:iphone-old-apps" /></template>
