<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lydcacblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lydcacblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:compass" /></template>
