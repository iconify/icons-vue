<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blmt__b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="blmt__b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-shopping-dark" /></template>
