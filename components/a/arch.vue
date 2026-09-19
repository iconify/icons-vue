<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtzzbcbez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtzzbcbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arch" /></template>
