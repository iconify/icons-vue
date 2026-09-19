<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqc49ei0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqc49ei0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-horizontal-right" /></template>
