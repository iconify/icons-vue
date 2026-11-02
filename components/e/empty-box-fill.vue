<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_7ptbbtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_7ptbbtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:empty-box-fill" /></template>
