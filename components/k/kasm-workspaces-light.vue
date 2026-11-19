<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nojp-xbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nojp-xbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kasm-workspaces-light" /></template>
