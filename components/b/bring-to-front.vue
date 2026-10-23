<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7p9wd7ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u7p9wd7ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:bring-to-front" /></template>
