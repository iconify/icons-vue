<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il8wh0bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il8wh0bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:archive" /></template>
