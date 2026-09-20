<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqj66qbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqj66qbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:circus-tent-bold" /></template>
