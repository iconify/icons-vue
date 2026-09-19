<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w61662vxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w61662vxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:key" /></template>
