<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg08ri5ny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg08ri5ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:assignment-code-filled" /></template>
