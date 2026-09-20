<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh2_e72fr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uh2_e72fr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cotton-bureau" /></template>
