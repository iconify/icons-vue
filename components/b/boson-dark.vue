<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2ej8gbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c2ej8gbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:boson-dark" /></template>
