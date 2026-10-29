<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p09h6hu5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p09h6hu5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:gift" /></template>
