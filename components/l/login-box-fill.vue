<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d28mddrnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d28mddrnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:login-box-fill" /></template>
