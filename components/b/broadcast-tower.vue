<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pob-uk1-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pob-uk1-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:broadcast-tower" /></template>
