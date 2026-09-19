<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rusai8b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rusai8b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:caret-down-square-filled" /></template>
