<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidjb1rhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qidjb1rhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:angle" /></template>
