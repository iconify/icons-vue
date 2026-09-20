<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj67-z5jn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mj67-z5jn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:faridoon-dark" /></template>
