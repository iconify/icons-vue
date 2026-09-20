<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_i8e7bst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_i8e7bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-right-bottom" /></template>
