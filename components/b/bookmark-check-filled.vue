<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7n5303_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7n5303_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bookmark-check-filled" /></template>
