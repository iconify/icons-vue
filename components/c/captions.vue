<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz42qgbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yz42qgbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:captions" /></template>
