<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7rl-cbvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7rl-cbvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:folder-add3-filled" /></template>
