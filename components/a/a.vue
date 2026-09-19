<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-v9lvbyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":563,"height":671};
const content = `<path class="w-v9lvbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:a" /></template>
