<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc2c4kgmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc2c4kgmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:brackets-content" /></template>
