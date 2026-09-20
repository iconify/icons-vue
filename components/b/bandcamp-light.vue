<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn4d89lsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kn4d89lsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:bandcamp-light" /></template>
