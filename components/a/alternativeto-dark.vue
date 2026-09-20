<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj_ed3blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sj_ed3blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alternativeto-dark" /></template>
