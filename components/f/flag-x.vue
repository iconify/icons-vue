<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lub6lcczs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lub6lcczs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flag-x" /></template>
