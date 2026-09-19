<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpos9jrlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="dpos9jrlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-stat" /></template>
