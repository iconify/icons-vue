<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz5hisb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sz5hisb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ferron-light" /></template>
