<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg5k18buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rg5k18buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:chevron-up-16-solid" /></template>
