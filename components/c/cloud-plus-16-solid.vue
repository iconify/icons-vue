<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/huzhlqb_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="huzhlqb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:cloud-plus-16-solid" /></template>
