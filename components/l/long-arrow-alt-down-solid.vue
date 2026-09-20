<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7kouvc9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h7kouvc9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:long-arrow-alt-down-solid" /></template>
