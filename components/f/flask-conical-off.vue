<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7pk1pbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e7pk1pbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:flask-conical-off" /></template>
