<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zekao-5lt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zekao-5lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:adminer" /></template>
