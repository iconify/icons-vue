<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu0ok6bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yu0ok6bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cred" /></template>
