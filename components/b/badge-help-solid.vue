<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1xnh5bpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1xnh5bpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:badge-help-solid" /></template>
