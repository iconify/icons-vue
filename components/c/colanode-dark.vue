<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqn0z4bic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wqn0z4bic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:colanode-dark" /></template>
