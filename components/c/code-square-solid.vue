<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgindvpcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgindvpcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:code-square-solid" /></template>
