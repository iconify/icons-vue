<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h1d-sni5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="h1d-sni5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:airpods-solid" /></template>
