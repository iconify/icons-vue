<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd5eemdne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd5eemdne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:book-square-filled" /></template>
