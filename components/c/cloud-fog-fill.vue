<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi6hjcbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bi6hjcbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:cloud-fog-fill" /></template>
