<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa_kbobxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="xa_kbobxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:hospital" /></template>
