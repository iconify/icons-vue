<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwzo6u-v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwzo6u-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:code-less-than" /></template>
