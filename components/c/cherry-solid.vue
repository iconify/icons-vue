<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3cy-4bql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3cy-4bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:cherry-solid" /></template>
