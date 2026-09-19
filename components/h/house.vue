<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye52r9bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ye52r9bed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:house" /></template>
