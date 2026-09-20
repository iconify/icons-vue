<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr_225bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr_225bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-diamond" /></template>
