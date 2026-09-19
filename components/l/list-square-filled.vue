<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve3cho81o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve3cho81o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:list-square-filled" /></template>
