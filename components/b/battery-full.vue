<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pitxv8bld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pitxv8bld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:battery-full" /></template>
