<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o07u8dbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o07u8dbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-in-down-right-dashed-panel-fill" /></template>
