<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc1i3zbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nc1i3zbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:electron-builder" /></template>
