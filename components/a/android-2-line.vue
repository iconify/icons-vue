<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kno2i6eul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kno2i6eul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:android-2-line" /></template>
