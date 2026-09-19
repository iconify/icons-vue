<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ta0-vub6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ta0-vub6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:guy-angel" /></template>
