<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/korl6q5lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="korl6q5lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:box-sign-remix" /></template>
