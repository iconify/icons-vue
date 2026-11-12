<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alabeshfc.css';
import '../../css/x/xblsrbb2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="alabeshfc"/><path class="xblsrbb2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-slides-light" /></template>
