<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5k2us3qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5k2us3qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:door-lock-box-fill" /></template>
