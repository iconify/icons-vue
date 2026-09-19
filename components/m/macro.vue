<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4rgmabsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w4rgmabsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:macro" /></template>
