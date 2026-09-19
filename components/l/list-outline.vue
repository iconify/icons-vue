<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fngrlybra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fngrlybra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:list-outline" /></template>
