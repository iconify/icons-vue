<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fup3d72ec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fup3d72ec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:7-zip-dark" /></template>
