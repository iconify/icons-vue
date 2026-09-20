<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7t-5kbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7t-5kbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-f" /></template>
