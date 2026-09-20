<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nzzc_c6ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nzzc_c6ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:git-pages-light" /></template>
