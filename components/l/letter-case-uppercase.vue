<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9d7tbcqd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="v9d7tbcqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:letter-case-uppercase" /></template>
