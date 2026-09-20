<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g024h_b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g024h_b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:attachment-list" /></template>
