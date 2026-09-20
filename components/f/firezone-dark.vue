<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh45pgscz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bh45pgscz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:firezone-dark" /></template>
