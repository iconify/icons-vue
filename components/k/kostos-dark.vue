<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uch3cth2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uch3cth2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kostos-dark" /></template>
