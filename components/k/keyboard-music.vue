<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqadbdcao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqadbdcao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:keyboard-music" /></template>
