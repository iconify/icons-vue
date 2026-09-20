<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkw51fnti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="pkw51fnti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:house-with-flag-and-info-i" /></template>
