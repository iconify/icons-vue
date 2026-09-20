<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y97_zp_7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="y97_zp_7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:badminton-racket-and-shuttlecock" /></template>
