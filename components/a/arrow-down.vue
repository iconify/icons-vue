<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egjj-sb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="egjj-sb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-down" /></template>
