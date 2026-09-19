<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/etxt3sbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etxt3sbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:calendar-close" /></template>
