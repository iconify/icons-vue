<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5cd61i2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5cd61i2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:fire-outline" /></template>
