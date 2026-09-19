<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-rl59bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x-rl59bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-cycle-fill-16" /></template>
