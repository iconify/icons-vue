<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j62v7-loa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j62v7-loa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:edit" /></template>
