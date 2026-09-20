<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2q_edbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2q_edbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:download-stack" /></template>
