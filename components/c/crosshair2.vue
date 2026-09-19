<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttl4pbbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ttl4pbbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:crosshair2" /></template>
