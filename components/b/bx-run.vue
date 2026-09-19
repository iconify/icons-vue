<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aovzl8biz.css';
import '../../css/o/oj1pjebiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="aovzl8biz"/><path class="oj1pjebiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-run" /></template>
