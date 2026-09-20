<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvimtok6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvimtok6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdrop-light" /></template>
