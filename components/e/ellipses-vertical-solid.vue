<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsyzbvbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tsyzbvbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:ellipses-vertical-solid" /></template>
