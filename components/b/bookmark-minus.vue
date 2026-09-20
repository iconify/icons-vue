<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4z83bxpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4z83bxpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:bookmark-minus" /></template>
