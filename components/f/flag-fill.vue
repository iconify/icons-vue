<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r466_pbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r466_pbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:flag-fill" /></template>
