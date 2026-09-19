<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpe3d1buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpe3d1buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bookmark-minus-filled" /></template>
