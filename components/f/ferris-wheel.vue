<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqekcgbmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqekcgbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:ferris-wheel" /></template>
