<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iopt-_0-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iopt-_0-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hook0-dark" /></template>
