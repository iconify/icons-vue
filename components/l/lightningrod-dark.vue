<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhp2ntaqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhp2ntaqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lightningrod-dark" /></template>
