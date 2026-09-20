<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekx1x_bqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekx1x_bqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:attic-assets-dark" /></template>
