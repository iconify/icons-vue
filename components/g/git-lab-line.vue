<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haxww0b3f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haxww0b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-lab-line" /></template>
