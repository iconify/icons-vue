<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob2v0kohw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob2v0kohw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:beachball-fill" /></template>
