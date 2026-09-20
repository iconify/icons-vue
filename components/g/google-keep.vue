<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfx72d7mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfx72d7mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:google-keep" /></template>
