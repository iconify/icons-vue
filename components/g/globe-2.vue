<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw3eezbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cw3eezbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:globe-2" /></template>
