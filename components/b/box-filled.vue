<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jq2axpyjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq2axpyjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:box-filled" /></template>
