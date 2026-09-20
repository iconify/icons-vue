<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn49wrlsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="nn49wrlsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:furniture" /></template>
