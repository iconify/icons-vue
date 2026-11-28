<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igzhn-bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="igzhn-bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:app-window-x" /></template>
