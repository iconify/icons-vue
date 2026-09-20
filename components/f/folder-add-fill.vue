<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-j2dobxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-j2dobxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-add-fill" /></template>
