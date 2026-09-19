<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzwd2419d.css';
import '../../css/g/gqvnp8-qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lzwd2419d"/><path class="gqvnp8-qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:crying" /></template>
