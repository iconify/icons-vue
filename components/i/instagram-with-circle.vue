<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es0hutbci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="es0hutbci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:instagram-with-circle" /></template>
