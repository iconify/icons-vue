<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r34k3ubvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r34k3ubvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:center-fill-12" /></template>
