<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hai481blp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hai481blp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-left-circle-fill" /></template>
