<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nc_d9_f0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nc_d9_f0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:check" /></template>
