<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjq9yqxug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjq9yqxug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-filled" /></template>
