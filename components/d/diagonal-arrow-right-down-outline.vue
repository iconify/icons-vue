<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1gsigb4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1gsigb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:diagonal-arrow-right-down-outline" /></template>
