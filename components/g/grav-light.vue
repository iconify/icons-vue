<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgy81lbpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sgy81lbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:grav-light" /></template>
