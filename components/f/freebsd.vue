<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfkgd6bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nfkgd6bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freebsd" /></template>
