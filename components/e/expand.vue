<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js0k_jnzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="js0k_jnzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:expand" /></template>
