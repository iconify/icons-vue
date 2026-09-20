<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o1k_lvbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1k_lvbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hash-circle" /></template>
