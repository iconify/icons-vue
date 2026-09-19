<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9oa2cb4l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9oa2cb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:female-condom-outline-24px" /></template>
