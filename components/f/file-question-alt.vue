<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko3zbfbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ko3zbfbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-question-alt" /></template>
