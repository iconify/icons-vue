<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr2fh6b0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cr2fh6b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:cercle-8" /></template>
