<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-7le-bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":448};
const content = `<path class="h-7le-bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:couple" /></template>
