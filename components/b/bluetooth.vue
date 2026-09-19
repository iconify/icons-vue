<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rejth40io.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rejth40io"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:bluetooth" /></template>
