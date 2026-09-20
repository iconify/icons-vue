<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqbie6beg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqbie6beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-title" /></template>
