<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp8_uebuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp8_uebuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grip" /></template>
