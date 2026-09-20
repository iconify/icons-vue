<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak5-1l7_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak5-1l7_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down3-filled" /></template>
