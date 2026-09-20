<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_mfb2qma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_mfb2qma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fast-forward-45" /></template>
