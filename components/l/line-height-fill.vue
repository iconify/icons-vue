<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc1q9kbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc1q9kbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-height-fill" /></template>
