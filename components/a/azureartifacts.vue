<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpl0lyb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpl0lyb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:azureartifacts" /></template>
