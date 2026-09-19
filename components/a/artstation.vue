<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs8yh4q5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cs8yh4q5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:artstation" /></template>
