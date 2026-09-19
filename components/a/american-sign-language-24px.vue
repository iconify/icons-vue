<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r18ywyxbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r18ywyxbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:american-sign-language-24px" /></template>
