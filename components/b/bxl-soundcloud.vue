<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kldny2m9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kldny2m9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-soundcloud" /></template>
