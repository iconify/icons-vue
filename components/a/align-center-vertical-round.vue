<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wajmslbkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wajmslbkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-center-vertical-round" /></template>
