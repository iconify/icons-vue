<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppv1d8b4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ppv1d8b4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freeshard-light" /></template>
