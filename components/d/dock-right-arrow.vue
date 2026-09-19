<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dz9iv6bwq.css';
import '../../css/p/pq0jslbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz9iv6bwq"/><path class="pq0jslbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-right-arrow" /></template>
