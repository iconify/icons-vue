<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc6a3p-ie.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="tc6a3p-ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-to-line" /></template>
