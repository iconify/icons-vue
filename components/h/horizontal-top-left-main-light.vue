<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecbe8r41d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecbe8r41d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:horizontal-top-left-main-light" /></template>
