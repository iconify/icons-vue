<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppw-j8-ys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppw-j8-ys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:heart" /></template>
