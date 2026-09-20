<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f35lopb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f35lopb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:gesture-open-filled" /></template>
