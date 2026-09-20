<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hndkjgbdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hndkjgbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-admob" /></template>
