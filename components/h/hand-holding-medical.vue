<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2iz5la8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="p2iz5la8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hand-holding-medical" /></template>
