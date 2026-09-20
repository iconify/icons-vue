<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aibd18w3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aibd18w3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:course-down-filled" /></template>
