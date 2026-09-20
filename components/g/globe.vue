<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob2n04b5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ob2n04b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:globe" /></template>
