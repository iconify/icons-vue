<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oadu9_skn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oadu9_skn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:club" /></template>
