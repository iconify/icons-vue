<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnxgm-9cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnxgm-9cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ease-out" /></template>
