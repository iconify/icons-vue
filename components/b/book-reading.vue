<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc2ri0bea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="sc2ri0bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:book-reading" /></template>
