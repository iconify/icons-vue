<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jlhyu9but.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlhyu9but"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-b" /></template>
