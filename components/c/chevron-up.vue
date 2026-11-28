<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig5d7vufz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig5d7vufz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevron-up" /></template>
