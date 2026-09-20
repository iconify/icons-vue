<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnx55hbvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnx55hbvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dash-menu" /></template>
