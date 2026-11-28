<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olo-xgmyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="olo-xgmyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bell-gear" /></template>
