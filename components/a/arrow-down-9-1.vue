<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqfe31b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="jqfe31b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrow-down-9-1" /></template>
