<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aeklnfbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeklnfbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:droplet-off-fill" /></template>
