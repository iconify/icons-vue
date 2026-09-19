<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/najw6-2ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="najw6-2ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ant" /></template>
