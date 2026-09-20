<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez6-9mb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez6-9mb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-page-break" /></template>
