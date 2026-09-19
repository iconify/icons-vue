<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trme8kb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="trme8kb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:circle-check" /></template>
