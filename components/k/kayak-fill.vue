<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnrhg7ivd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnrhg7ivd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:kayak-fill" /></template>
