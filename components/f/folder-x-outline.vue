<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxi8d7bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vxi8d7bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-x-outline" /></template>
