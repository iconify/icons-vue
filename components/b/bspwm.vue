<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7d2ywa-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a7d2ywa-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bspwm" /></template>
