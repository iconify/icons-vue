<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eie6a02dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eie6a02dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ladder-off" /></template>
