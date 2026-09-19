<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq19trb5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uq19trb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:indent-right" /></template>
