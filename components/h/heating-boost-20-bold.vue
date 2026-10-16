<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omf76gbof.css';
import '../../css/f/f40uyxeum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="omf76gbof"/><path class="f40uyxeum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heating-boost-20-bold" /></template>
