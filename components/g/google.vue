<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1f2wrbyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":512};
const content = `<path class="g1f2wrbyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:google" /></template>
