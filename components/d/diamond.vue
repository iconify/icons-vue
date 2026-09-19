<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8p-l6boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d8p-l6boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:diamond" /></template>
