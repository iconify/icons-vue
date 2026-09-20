<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhyv3qbpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rhyv3qbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:cross-circled" /></template>
