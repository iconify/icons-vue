<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgkdrkbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgkdrkbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dialogue-minus-outline" /></template>
