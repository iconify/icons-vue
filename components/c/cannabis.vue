<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkb4mob0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pkb4mob0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cannabis" /></template>
