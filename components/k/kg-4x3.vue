<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glbu6gb9k.css';
import '../../css/x/x-vljeb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="glbu6gb9k"/><path class="x-vljeb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:kg-4x3" /></template>
