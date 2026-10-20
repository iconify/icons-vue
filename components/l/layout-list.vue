<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvwn4ccwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwn4ccwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:layout-list" /></template>
