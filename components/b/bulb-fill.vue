<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf-_avbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jf-_avbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-fill" /></template>
