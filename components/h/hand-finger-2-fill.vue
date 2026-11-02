<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea0-w_xym.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea0-w_xym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hand-finger-2-fill" /></template>
