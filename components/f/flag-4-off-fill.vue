<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_ng6supk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_ng6supk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flag-4-off-fill" /></template>
