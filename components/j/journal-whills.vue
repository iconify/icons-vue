<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mipg4xb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="mipg4xb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:journal-whills" /></template>
