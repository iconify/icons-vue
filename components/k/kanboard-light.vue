<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks_7jybyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ks_7jybyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kanboard-light" /></template>
