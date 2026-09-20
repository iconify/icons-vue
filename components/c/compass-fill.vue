<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2gufpr0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2gufpr0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:compass-fill" /></template>
