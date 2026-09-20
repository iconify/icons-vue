<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/abgai4bzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abgai4bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:instrument-line" /></template>
