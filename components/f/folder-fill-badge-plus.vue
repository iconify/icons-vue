<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0bt5t-7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m0bt5t-7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:folder-fill-badge-plus" /></template>
