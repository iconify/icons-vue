<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3eu34blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3eu34blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:component" /></template>
