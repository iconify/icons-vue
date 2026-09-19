<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ori4jfh0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ori4jfh0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bacteria-filled" /></template>
