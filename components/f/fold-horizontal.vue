<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4ttsc5cl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4ttsc5cl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:fold-horizontal" /></template>
