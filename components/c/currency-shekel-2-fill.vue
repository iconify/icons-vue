<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7jmtbc2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7jmtbc2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-shekel-2-fill" /></template>
