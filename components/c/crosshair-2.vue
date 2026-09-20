<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trlk_bt4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="trlk_bt4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:crosshair-2" /></template>
