<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq8ar2_bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mq8ar2_bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-generic-fill-12" /></template>
