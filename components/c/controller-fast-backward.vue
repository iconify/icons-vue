<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oua5ruzrk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oua5ruzrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:controller-fast-backward" /></template>
