<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzswmf6nk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzswmf6nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump-color:focus-points" /></template>
