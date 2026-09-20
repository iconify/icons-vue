<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5r7npblp.css';
import '../../css/y/yxi16mj3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h5r7npblp"/><path class="yxi16mj3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:1panel-dark" /></template>
