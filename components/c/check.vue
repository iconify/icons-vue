<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/db-1jbcvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1600,"height":1280};
const content = `<path class="db-1jbcvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:check" /></template>
