<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjp1dex-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjp1dex-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:filecoin" /></template>
