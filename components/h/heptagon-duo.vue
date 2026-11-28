<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic2dd_baz.css';
import '../../css/d/do9zq7gwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic2dd_baz secondary"/><path class="do9zq7gwa primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:heptagon-duo" /></template>
