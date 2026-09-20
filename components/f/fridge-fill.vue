<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zef7wjgei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zef7wjgei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fridge-fill" /></template>
