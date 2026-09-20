<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2m4dbec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xi2m4dbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:lunar-light" /></template>
