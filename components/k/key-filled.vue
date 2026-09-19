<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4t5k-aiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4t5k-aiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:key-filled" /></template>
