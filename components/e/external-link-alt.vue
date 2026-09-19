<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf842gvyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uf842gvyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:external-link-alt" /></template>
