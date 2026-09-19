<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3kgvnb-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y3kgvnb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:clock-o" /></template>
