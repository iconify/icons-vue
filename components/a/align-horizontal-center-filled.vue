<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upt5e3o1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upt5e3o1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-horizontal-center-filled" /></template>
