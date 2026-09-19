<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk3cacbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zk3cacbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-rm-o" /></template>
