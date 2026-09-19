<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uznf0tbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uznf0tbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:headphone-solid" /></template>
