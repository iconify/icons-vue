<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6xfb8lhn.css';
import '../../css/e/ebf-dhbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u6xfb8lhn"/><path class="ebf-dhbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:geeftlist-dark" /></template>
