<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmre1_bvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmre1_bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-l" /></template>
