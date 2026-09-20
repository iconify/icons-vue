<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4mr0ebnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4mr0ebnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:ghost-indifferent" /></template>
