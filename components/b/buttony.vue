<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf6cugnxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cf6cugnxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:buttony" /></template>
