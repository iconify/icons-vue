<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0qybk50m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h0qybk50m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-jump-to-start" /></template>
