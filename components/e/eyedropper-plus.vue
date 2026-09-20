<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozs0v31rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozs0v31rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eyedropper-plus" /></template>
