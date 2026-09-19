<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dtk5vsb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtk5vsb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:baby-0203-alt-24px" /></template>
