<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cukjm2ikv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cukjm2ikv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:letter-case-capitalize" /></template>
