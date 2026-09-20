<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd_w473vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vd_w473vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:field-16" /></template>
