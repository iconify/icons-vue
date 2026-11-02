<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atgh7sbfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atgh7sbfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:close-small-line" /></template>
