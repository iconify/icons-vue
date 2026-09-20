<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h006f82xz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h006f82xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:faved-light" /></template>
