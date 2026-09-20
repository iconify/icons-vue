<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvbc9mblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kvbc9mblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libreoffice" /></template>
