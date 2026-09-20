<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gave4vgwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gave4vgwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:flint-dark" /></template>
