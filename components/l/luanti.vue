<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxd0bvbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxd0bvbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:luanti" /></template>
