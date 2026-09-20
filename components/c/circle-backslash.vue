<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2c55hbbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q2c55hbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:circle-backslash" /></template>
