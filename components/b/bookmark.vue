<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ot6ubat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6ot6ubat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:bookmark" /></template>
