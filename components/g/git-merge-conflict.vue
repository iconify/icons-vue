<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke_6hnbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke_6hnbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:git-merge-conflict" /></template>
