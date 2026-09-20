<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esbz12vtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esbz12vtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:contacts-filled" /></template>
