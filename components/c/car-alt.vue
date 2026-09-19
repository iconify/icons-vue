<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipgh2pb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipgh2pb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:car-alt" /></template>
