<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppek0zx8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppek0zx8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:6-plus" /></template>
