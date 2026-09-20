<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d69ufpi7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d69ufpi7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubuntu-light" /></template>
