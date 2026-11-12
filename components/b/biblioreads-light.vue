<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fuj-_3t9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fuj-_3t9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:biblioreads-light" /></template>
