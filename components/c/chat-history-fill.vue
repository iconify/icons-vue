<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euhpbhsyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euhpbhsyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:chat-history-fill" /></template>
