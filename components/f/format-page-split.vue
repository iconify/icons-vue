<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbggd5yiz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbggd5yiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-page-split" /></template>
