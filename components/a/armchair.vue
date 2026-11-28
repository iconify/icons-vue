<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8y8u4wiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8y8u4wiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:armchair" /></template>
