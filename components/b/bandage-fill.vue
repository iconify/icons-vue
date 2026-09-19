<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2fllcyck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="h2fllcyck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bandage-fill" /></template>
