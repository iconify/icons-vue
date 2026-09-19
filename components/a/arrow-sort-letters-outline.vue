<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsf7ge_8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsf7ge_8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:arrow-sort-letters-outline" /></template>
