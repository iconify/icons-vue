<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p79vmbtic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p79vmbtic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:juejin" /></template>
