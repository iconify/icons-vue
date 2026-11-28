<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eng1o0dzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eng1o0dzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:dropdown-check" /></template>
