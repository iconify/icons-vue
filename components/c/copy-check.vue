<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grhdxjbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grhdxjbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:copy-check" /></template>
