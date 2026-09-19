<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b039fzbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b039fzbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:at" /></template>
