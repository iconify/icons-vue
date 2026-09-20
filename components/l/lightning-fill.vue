<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs7a71euu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hs7a71euu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lightning-fill" /></template>
