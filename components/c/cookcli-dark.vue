<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk0k5hb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rk0k5hb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cookcli-dark" /></template>
