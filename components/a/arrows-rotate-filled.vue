<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctd19f6wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctd19f6wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrows-rotate-filled" /></template>
