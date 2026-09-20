<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn_3n2bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn_3n2bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hitkeep" /></template>
