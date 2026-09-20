<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_86mbcpr.css';
import '../../css/c/c8vd1xbye.css';
import '../../css/z/z05_jybpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_86mbcpr"/><path class="c8vd1xbye"/><path class="z05_jybpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bat" /></template>
