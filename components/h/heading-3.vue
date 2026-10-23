<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apu_4kbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apu_4kbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-3" /></template>
