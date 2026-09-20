<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz28ocrgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz28ocrgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-check-fill" /></template>
