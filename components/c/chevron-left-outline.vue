<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isns3yuhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isns3yuhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:chevron-left-outline" /></template>
