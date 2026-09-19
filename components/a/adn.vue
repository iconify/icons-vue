<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1ybyoq8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="s1ybyoq8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:adn" /></template>
