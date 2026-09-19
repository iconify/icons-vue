<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r708_dubz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r708_dubz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:hand-fist" /></template>
