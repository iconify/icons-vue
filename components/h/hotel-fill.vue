<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8h8i1yra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8h8i1yra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:hotel-fill" /></template>
