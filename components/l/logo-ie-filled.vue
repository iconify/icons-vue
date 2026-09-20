<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-d-gcptl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-d-gcptl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:logo-ie-filled" /></template>
