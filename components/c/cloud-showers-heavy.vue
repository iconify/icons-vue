<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3f0bobfk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3f0bobfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:cloud-showers-heavy" /></template>
