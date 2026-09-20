<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnsxyzb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnsxyzb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kfc-legacy" /></template>
