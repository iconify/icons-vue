<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic27p1byo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic27p1byo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:fairphone" /></template>
