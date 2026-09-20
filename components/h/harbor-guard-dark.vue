<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3se15b8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k3se15b8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:harbor-guard-dark" /></template>
