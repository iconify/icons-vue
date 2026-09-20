<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1l45ccjy.css';
import '../../css/b/b-5uoz78u.css';
import '../../css/a/a4yfnabqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1l45ccjy"/><path class="b-5uoz78u"/><path class="a4yfnabqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:avt" /></template>
