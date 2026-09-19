<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ushy56l0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="ushy56l0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:dolly" /></template>
