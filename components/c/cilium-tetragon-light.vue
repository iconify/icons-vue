<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_n7pbc6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m_n7pbc6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-tetragon-light" /></template>
