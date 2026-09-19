<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s17z00b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s17z00b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:gripper-tool" /></template>
