<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de0b7s82y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de0b7s82y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:comma" /></template>
