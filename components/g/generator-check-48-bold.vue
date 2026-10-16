<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koz4nrgjs.css';
import '../../css/s/st5lvs5dl.css';
import '../../css/y/y9mg2tbzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="koz4nrgjs"/><path class="st5lvs5dl"/><path class="y9mg2tbzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:generator-check-48-bold" /></template>
