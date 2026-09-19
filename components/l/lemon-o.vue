<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfzas2b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="cfzas2b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:lemon-o" /></template>
