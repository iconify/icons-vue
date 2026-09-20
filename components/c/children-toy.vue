<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy7ho_3pd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy7ho_3pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:children-toy" /></template>
