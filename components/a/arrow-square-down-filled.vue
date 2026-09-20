<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah8l-e6gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah8l-e6gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-square-down-filled" /></template>
