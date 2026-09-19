<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h84l40bgj.css';
import '../../css/w/wckr9kb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h84l40bgj"/><path class="wckr9kb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-circle-left-outline" /></template>
