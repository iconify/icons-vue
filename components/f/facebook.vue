<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8i-fmzkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8i-fmzkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:facebook" /></template>
