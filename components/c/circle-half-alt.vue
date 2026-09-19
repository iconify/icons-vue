<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxz_4f-mz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxz_4f-mz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:circle-half-alt" /></template>
