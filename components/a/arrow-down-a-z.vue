<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gh6o4c0gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gh6o4c0gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-down-a-z" /></template>
