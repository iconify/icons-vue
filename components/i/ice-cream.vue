<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p26oc5e-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="p26oc5e-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:ice-cream" /></template>
