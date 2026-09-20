<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p42wrwb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p42wrwb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:casaos-light" /></template>
