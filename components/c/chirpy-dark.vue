<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud1ko8bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ud1ko8bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chirpy-dark" /></template>
