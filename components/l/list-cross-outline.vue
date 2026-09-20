<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjvcbvbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjvcbvbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-cross-outline" /></template>
