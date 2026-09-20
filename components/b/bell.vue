<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0scjib0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="p0scjib0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:bell" /></template>
