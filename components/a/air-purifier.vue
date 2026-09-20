<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxo43ab3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxo43ab3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:air-purifier" /></template>
