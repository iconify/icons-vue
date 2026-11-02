<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjng15r9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjng15r9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-heart-line" /></template>
