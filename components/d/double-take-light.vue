<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4wb2pdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ec4wb2pdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:double-take-light" /></template>
