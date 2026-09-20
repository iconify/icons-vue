<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/me-v67brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="me-v67brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-add-1-expand-cross-buttons-button-more-remove-plus-add" /></template>
