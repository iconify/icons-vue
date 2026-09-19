<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvub7-qvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vvub7-qvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:cube-sharp" /></template>
