<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-_fu4bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-_fu4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-plus" /></template>
