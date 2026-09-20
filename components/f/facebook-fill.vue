<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ava2r5bmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ava2r5bmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:facebook-fill" /></template>
