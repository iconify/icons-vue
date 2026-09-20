<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f30p36brj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f30p36brj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cilium-tetragon-dark" /></template>
