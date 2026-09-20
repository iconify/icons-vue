<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj7zo_i3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nj7zo_i3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:hexagon" /></template>
