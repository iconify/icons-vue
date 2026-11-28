<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a25g90ajj.css';
import '../../css/o/oa9edkb7e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a25g90ajj secondary"/><path class="oa9edkb7e primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bookmark-duo" /></template>
