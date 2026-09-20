<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enis4sb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="enis4sb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:imdb-dark" /></template>
