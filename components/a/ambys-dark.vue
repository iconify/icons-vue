<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgx99j8cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dgx99j8cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ambys-dark" /></template>
