<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv5s23ivq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nv5s23ivq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:list-check" /></template>
