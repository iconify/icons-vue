<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsf40n85b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsf40n85b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:caret-left-right-filled" /></template>
