<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swq9uvb0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="swq9uvb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apple-light" /></template>
