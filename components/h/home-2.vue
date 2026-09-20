<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drk3p-42n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drk3p-42n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-2" /></template>
