<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-vi90bdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="m-vi90bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:layer-group" /></template>
