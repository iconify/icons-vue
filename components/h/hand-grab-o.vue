<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un8-nx_wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1408};
const content = `<path class="un8-nx_wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:hand-grab-o" /></template>
