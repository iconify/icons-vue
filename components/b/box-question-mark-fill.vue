<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a22dcsy8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a22dcsy8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-question-mark-fill" /></template>
