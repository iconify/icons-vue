<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eey-7uxwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eey-7uxwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fish-under-paragraph" /></template>
