<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu-_0514m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu-_0514m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-down-3" /></template>
