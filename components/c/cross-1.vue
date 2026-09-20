<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz8t8__qs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vz8t8__qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:cross-1" /></template>
