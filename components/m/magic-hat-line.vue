<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqggstbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqggstbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:magic-hat-line" /></template>
