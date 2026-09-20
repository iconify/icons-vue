<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb-s_fb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eb-s_fb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-right-up-filled" /></template>
