<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ag8w_1_qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag8w_1_qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-up-1" /></template>
