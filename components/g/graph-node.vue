<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncs1tuokk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ncs1tuokk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:graph-node" /></template>
