<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3jht4bnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f3jht4bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:globe-stroke-20" /></template>
