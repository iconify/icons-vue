<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8eno1bal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8eno1bal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:extension-filled" /></template>
