<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp4j6nmbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp4j6nmbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-line" /></template>
