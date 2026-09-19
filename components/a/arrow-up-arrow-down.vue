<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6bu27d_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c6bu27d_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:arrow-up-arrow-down" /></template>
