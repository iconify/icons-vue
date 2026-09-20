<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp5hn5bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp5hn5bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-word-filled" /></template>
