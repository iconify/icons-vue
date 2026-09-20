<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcghp2bbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xcghp2bbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:look-right-fill" /></template>
