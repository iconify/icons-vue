<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5rb22bzv.css';
import '../../css/a/ad4ln5bah.css';
import '../../css/y/y0wutcc8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5rb22bzv"/><path class="ad4ln5bah"/><path class="y0wutcc8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dawarich-dark" /></template>
