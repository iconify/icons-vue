<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h39unjboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h39unjboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-path-rounded-square-solid" /></template>
