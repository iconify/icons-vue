<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnn_g043v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn_g043v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-broken" /></template>
