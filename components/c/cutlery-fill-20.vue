<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8wh20b4s.css';
import '../../css/t/tatmy1kfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s8wh20b4s"/><path class="tatmy1kfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:cutlery-fill-20" /></template>
