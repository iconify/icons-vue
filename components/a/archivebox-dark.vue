<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5ob8_bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k5ob8_bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:archivebox-dark" /></template>
