<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2qx0lb9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="p2qx0lb9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:facial-recognition-scan" /></template>
