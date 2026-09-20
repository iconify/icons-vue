<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssfz_ebsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ssfz_ebsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inkscape-dark" /></template>
