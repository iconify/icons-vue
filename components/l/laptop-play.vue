<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skhk0if-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skhk0if-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:laptop-play" /></template>
