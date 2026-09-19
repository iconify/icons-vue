<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xs2w-lbzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="xs2w-lbzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-up" /></template>
