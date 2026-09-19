<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wbw0lvbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbw0lvbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:arrow-up" /></template>
