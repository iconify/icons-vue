<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_-c_yr1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_-c_yr1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:krakend-light" /></template>
