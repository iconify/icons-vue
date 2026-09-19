<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z54wf7bqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z54wf7bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:checkmark-square-2-fill" /></template>
