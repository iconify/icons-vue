<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbvvh5dtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbvvh5dtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:diagonal-arrow-left-up-fill" /></template>
