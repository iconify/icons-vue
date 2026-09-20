<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb00oo3bp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb00oo3bp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:clipboard-list" /></template>
