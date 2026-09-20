<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dganpjjey.css';
import '../../css/f/fna3t83oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dganpjjey"/><path class="fna3t83oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:javascript" /></template>
