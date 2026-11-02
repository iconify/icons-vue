<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c58r33bla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c58r33bla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-top-close-fill" /></template>
