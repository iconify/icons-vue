<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew7uyrbgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew7uyrbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-plus" /></template>
