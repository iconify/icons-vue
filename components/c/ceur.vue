<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_r13u14c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_r13u14c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:ceur" /></template>
