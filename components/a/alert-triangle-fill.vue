<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbs_-r7it.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbs_-r7it"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:alert-triangle-fill" /></template>
