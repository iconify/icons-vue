<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il6uzfbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il6uzfbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-bottom-2-fill" /></template>
