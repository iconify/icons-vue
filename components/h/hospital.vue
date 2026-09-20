<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6w-tlz_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="c6w-tlz_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:hospital" /></template>
