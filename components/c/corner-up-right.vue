<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khjmoju2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khjmoju2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:corner-up-right" /></template>
