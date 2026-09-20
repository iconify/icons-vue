<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqeo4nzcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uqeo4nzcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:key-shift-16" /></template>
