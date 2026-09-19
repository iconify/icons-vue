<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydb42tbaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydb42tbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:cluster" /></template>
