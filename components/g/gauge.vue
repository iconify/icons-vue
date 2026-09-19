<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q5et1ab9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q5et1ab9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:gauge" /></template>
