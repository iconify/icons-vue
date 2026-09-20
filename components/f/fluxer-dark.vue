<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esoknpbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="esoknpbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fluxer-dark" /></template>
