<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vonv1ccfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vonv1ccfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:elementaryos" /></template>
