<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/witqilbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="witqilbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:enj" /></template>
