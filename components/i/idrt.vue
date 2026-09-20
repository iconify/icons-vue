<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gufv3ebnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gufv3ebnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:idrt" /></template>
