<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/na57upbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="na57upbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:equal-not-fill-round" /></template>
