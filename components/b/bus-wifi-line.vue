<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py3fc3blf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py3fc3blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bus-wifi-line" /></template>
