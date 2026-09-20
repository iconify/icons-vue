<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxs-f7bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxs-f7bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-vertical-fill" /></template>
