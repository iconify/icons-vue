<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xag_4tblj.css';
import '../../css/w/wjb62bbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer xag_4tblj"/><path class="duoicon-primary-layer wjb62bbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:folder-open" /></template>
