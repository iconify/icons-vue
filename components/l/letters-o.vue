<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu4v9lb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu4v9lb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-o" /></template>
