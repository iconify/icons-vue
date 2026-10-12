<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4el2fric.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4el2fric"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:cellular-network-2g" /></template>
