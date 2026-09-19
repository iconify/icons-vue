<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd8yle12b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1888,"height":1408};
const content = `<path class="pd8yle12b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:folder-open" /></template>
