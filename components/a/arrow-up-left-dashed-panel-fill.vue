<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdv40tb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdv40tb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-left-dashed-panel-fill" /></template>
