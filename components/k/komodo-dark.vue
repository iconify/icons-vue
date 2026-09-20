<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks8q3gsxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ks8q3gsxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:komodo-dark" /></template>
