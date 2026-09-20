<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjvz-qrwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pjvz-qrwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:emoji-2-fill" /></template>
