<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n01_iubvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n01_iubvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bookbub" /></template>
