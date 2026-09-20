<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daw8iibis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daw8iibis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-minus-outline" /></template>
