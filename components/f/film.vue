<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyrjncbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyrjncbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:film" /></template>
