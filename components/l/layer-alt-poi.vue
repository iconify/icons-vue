<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szdg7sb9v.css';
import '../../css/i/inw9uqdux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="szdg7sb9v"/><path class="inw9uqdux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:layer-alt-poi" /></template>
