<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwrtmg0fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="lwrtmg0fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:grid" /></template>
