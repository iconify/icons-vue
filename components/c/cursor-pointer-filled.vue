<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iamwjnotf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iamwjnotf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cursor-pointer-filled" /></template>
