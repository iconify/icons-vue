<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx6p4trgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lx6p4trgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gabled-roof-with-fireplace-and-chimney" /></template>
