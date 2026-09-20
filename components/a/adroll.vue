<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssw7l0b2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssw7l0b2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:adroll" /></template>
