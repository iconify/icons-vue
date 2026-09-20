<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgu-cdbxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bgu-cdbxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:keila" /></template>
