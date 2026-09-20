<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcxj3j5_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wcxj3j5_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:eye-o" /></template>
