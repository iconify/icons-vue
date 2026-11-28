<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0v10vboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0v10vboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hand-truck" /></template>
