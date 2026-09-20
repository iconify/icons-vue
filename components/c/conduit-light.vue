<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnzr4nojc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nnzr4nojc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:conduit-light" /></template>
