<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq5e-62yy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq5e-62yy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:alphaxiv" /></template>
