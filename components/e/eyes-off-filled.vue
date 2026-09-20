<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdngy1b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdngy1b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:eyes-off-filled" /></template>
