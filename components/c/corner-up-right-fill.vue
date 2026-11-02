<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsnmn6bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsnmn6bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-up-right-fill" /></template>
