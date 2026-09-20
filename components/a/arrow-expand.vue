<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ju6kq_tox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju6kq_tox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:arrow-expand" /></template>
