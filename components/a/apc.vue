<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_gf5r_uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_gf5r_uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apc" /></template>
