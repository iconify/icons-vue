<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h79i-qaqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h79i-qaqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:ember" /></template>
