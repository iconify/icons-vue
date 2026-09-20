<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rns20ob0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rns20ob0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:angry-filled" /></template>
