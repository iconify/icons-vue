<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izg_gnb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="izg_gnb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:component-1" /></template>
