<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o83ojebcx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o83ojebcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:handbag-fill" /></template>
