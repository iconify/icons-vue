<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7ipksbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7ipksbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-floor-minus-one" /></template>
