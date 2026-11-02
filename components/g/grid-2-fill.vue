<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxi646-cx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxi646-cx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:grid-2-fill" /></template>
