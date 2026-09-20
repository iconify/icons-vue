<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yau_oxycf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="yau_oxycf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:arrow-bottom-left" /></template>
