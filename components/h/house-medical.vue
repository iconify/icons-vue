<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8t73ccrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="n8t73ccrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:house-medical" /></template>
