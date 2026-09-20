<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onwip71vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="onwip71vm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:eyebrow" /></template>
