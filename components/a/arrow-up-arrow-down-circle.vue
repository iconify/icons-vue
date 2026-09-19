<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/helklwb1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="helklwb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-up-arrow-down-circle" /></template>
