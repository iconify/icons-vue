<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x73dy-y1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x73dy-y1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:asterisk-2-fill" /></template>
