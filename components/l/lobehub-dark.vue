<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jstim82hi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jstim82hi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lobehub-dark" /></template>
