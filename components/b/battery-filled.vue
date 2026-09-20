<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-h01obyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-h01obyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:battery-filled" /></template>
