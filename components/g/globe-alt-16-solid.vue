<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t36ap-bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t36ap-bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:globe-alt-16-solid" /></template>
