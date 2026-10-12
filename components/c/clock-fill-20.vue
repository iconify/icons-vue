<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f71l33bgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f71l33bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-fill-20" /></template>
