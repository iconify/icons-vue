<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrw5pbbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="xrw5pbbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:all-sides" /></template>
