<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4jlqkbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4jlqkbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:environment" /></template>
