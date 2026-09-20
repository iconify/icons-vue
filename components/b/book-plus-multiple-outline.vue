<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbucz-2oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbucz-2oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-plus-multiple-outline" /></template>
