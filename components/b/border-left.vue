<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9hlq-bmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9hlq-bmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-left" /></template>
