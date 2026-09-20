<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gr94q88qj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr94q88qj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fluent" /></template>
