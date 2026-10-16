<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqoz6vy8q.css';
import '../../css/p/pi9uz4b0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qqoz6vy8q"/><path class="pi9uz4b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:haze-20-bold" /></template>
