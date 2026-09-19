<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfpjjcc0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="pfpjjcc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ghost" /></template>
