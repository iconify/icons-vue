<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dus9g0b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dus9g0b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:indent-decrease-20" /></template>
