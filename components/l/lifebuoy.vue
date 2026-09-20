<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hz9iuq2bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hz9iuq2bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:lifebuoy" /></template>
