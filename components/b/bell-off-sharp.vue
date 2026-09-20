<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te2583bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te2583bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bell-off-sharp" /></template>
