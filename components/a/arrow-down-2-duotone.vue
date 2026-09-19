<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr6bbj9he.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr6bbj9he"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-down-2-duotone" /></template>
