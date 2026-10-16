<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w01dflzvf.css';
import '../../css/y/y5lz0kbah.css';
import '../../css/m/mv7ibobfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w01dflzvf"/><path class="y5lz0kbah"/><path class="mv7ibobfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-line-dots-20-bold" /></template>
