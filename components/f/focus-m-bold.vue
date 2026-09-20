<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tryhe-3gz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tryhe-3gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:focus-m-bold" /></template>
