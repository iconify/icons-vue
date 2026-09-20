<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wsdbv17zy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1400.1,"height":452.4,"left":-0.03,"top":-0.03};
const content = `<path class="wsdbv17zy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:harvard" /></template>
