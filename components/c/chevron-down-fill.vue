<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n-_jerb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-_jerb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:chevron-down-fill" /></template>
