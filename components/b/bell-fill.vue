<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbyuzub8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hbyuzub8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:bell-fill" /></template>
