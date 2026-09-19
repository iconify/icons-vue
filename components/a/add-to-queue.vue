<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoy6vkbrs.css';
import '../../css/l/lbf20db5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoy6vkbrs"/><path class="lbf20db5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:add-to-queue" /></template>
