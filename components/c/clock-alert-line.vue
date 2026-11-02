<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncirv0fnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncirv0fnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-alert-line" /></template>
