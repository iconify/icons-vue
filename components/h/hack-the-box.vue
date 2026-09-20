<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r860s5b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r860s5b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:hack-the-box" /></template>
