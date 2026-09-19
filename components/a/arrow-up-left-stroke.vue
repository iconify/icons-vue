<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sy7qwsk3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy7qwsk3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-left-stroke" /></template>
