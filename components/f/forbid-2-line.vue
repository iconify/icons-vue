<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfcn2tbwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfcn2tbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forbid-2-line" /></template>
