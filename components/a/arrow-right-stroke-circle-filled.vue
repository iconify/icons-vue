<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttsypeb5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ttsypeb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-stroke-circle-filled" /></template>
