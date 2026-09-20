<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck8dsdbbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8dsdbbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:air-condition-open-line" /></template>
