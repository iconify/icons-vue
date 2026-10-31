<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ad0u0jetp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad0u0jetp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-fill-round" /></template>
