<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw33au4cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw33au4cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:first-aid-kit-line" /></template>
