<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waryrco8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waryrco8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:list-collapse-solid" /></template>
