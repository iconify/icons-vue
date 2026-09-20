<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz7b8nbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="xz7b8nbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:create" /></template>
