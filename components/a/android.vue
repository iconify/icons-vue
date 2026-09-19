<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2ecztt3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":520};
const content = `<path class="b2ecztt3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:android" /></template>
