<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b731n-1fx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b731n-1fx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bird-line" /></template>
