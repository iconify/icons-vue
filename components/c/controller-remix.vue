<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_-bdxbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="t_-bdxbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:controller-remix" /></template>
