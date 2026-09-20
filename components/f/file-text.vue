<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyyvbkb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyyvbkb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-text" /></template>
