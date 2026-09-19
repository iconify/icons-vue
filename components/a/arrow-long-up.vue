<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eg46exbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg46exbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:arrow-long-up" /></template>
