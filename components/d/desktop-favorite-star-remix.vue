<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhpxol20x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yhpxol20x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:desktop-favorite-star-remix" /></template>
