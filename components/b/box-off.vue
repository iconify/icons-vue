<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chyf5xbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chyf5xbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-off" /></template>
