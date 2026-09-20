<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on1p6hbis.css';
import '../../css/w/w2-97pbpu.css';
import '../../css/a/au6i7gblr.css';
import '../../css/p/pwmwo4bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on1p6hbis"/><path class="w2-97pbpu"/><path class="au6i7gblr"/><path class="pwmwo4bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:email-action-delete-junk-1" /></template>
