<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4d64nlhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4d64nlhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-n" /></template>
