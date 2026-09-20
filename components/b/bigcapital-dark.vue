<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znep9ab-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znep9ab-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bigcapital-dark" /></template>
