<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndik99b6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ndik99b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:css-16" /></template>
