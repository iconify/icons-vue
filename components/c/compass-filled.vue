<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlx4obcue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlx4obcue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:compass-filled" /></template>
