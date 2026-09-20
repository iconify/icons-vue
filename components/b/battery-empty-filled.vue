<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se-1--b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se-1--b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:battery-empty-filled" /></template>
