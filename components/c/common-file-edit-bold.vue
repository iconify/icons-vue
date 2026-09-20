<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5lczrbjj.css';
import '../../css/w/w_gjrzbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5lczrbjj"/><path class="w_gjrzbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-edit-bold" /></template>
