<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9bi5tb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9bi5tb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:brightness-plus" /></template>
