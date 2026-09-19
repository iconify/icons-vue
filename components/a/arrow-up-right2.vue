<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_6j5db4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e_6j5db4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:arrow-up-right2" /></template>
