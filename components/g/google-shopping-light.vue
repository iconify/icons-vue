<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whv-2bcvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="whv-2bcvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-shopping-light" /></template>
