<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqu2aeb_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mqu2aeb_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:creative-commons-noncommercial-eu" /></template>
