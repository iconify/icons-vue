<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyvqyt90u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iyvqyt90u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-exclamation-20-solid" /></template>
