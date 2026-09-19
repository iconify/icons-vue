<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1c1yib-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="m1c1yib-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-regular:hand-point-left" /></template>
