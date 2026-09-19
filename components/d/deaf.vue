<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf_p894yt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nf_p894yt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:deaf" /></template>
