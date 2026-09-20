<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui5n0ibde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="ui5n0ibde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-circle-down-f" /></template>
