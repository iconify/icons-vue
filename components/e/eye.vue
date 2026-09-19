<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1ebvg0wo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="l1ebvg0wo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:eye" /></template>
