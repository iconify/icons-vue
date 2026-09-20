<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7cy4nbyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7cy4nbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:caret-right-small" /></template>
