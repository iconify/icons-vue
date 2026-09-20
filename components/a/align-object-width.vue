<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrojnzb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="rrojnzb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-object-width" /></template>
