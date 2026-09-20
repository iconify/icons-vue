<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6_yh2qxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_yh2qxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:dots-vertical" /></template>
