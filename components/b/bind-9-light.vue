<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u2qajxb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u2qajxb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bind-9-light" /></template>
