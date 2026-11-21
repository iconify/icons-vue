<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl153uk6t.css';
import '../../css/r/rv21otbpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl153uk6t"/><path class="rv21otbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layer-arrow-down-filled" /></template>
