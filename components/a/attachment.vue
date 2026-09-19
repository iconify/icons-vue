<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaxc49cjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yaxc49cjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:attachment" /></template>
