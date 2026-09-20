<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw5equbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw5equbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:book-heart-solid" /></template>
