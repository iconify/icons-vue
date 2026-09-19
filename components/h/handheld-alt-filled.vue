<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omcg5ebpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omcg5ebpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld-alt-filled" /></template>
