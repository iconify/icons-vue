<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl3bd5ipw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wl3bd5ipw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:jstor-dark" /></template>
