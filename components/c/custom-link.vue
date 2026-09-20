<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iju81lxdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="iju81lxdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:custom-link" /></template>
