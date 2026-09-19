<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bq5k6h_1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bq5k6h_1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:fax" /></template>
