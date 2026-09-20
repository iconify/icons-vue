<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0m3lcb0w.css';
import '../../css/o/on5ils5mm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0m3lcb0w"/><path class="on5ils5mm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:invoice" /></template>
