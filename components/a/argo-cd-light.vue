<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9wgbmbqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9wgbmbqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:argo-cd-light" /></template>
