<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc5li9bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oc5li9bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-setting-cog" /></template>
