<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0d0xub9d.css';
import '../../css/y/yqu1ju23x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0d0xub9d"/><path class="yqu1ju23x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-check-48-bold" /></template>
