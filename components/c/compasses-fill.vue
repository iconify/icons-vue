<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uov_89a-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uov_89a-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:compasses-fill" /></template>
