<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9bt45sko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9bt45sko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mail-line" /></template>
