<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl35e_bvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gl35e_bvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:animal-donkey" /></template>
