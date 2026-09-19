<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rfj8gvdlk.css';
import '../../css/v/vlqkedb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfj8gvdlk"/><path class="vlqkedb5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:image-on" /></template>
