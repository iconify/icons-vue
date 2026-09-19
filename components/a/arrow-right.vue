<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_49-e-9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h_49-e-9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right" /></template>
