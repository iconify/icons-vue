<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x04vd8uuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x04vd8uuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:arrow-up-left-circle-fill" /></template>
