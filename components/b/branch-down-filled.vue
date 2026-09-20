<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk8rr7b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vk8rr7b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:branch-down-filled" /></template>
