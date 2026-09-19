<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxvnz6ymq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxvnz6ymq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:folder-arrow-down" /></template>
