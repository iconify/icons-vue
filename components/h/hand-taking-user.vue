<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c309e1k6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c309e1k6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hand-taking-user" /></template>
