<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk8vunbuz.css';
import '../../css/j/jb0hwxb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8vunbuz"/><path clip-rule="evenodd" class="jb0hwxb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:emoji-expressionless" /></template>
