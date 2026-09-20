<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq70-9bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq70-9bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-up-fill" /></template>
