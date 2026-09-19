<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsweqxb6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsweqxb6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:android-fill" /></template>
