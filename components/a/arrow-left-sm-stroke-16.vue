<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jaybi2sll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jaybi2sll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:arrow-left-sm-stroke-16" /></template>
