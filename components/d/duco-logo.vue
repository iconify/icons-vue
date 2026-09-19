<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arn61nloh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arn61nloh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:duco-logo" /></template>
