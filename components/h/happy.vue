<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7w-1fbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k7w-1fbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:happy" /></template>
