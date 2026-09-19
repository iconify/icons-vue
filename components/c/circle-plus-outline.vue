<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwou52g1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uwou52g1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:circle-plus-outline" /></template>
