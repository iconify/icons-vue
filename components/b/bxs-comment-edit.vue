<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nhbfye42t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhbfye42t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-comment-edit" /></template>
