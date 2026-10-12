<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ruzkcwbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ruzkcwbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:check-box-double-fill-20" /></template>
