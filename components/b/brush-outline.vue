<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avk0e-lpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avk0e-lpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:brush-outline" /></template>
