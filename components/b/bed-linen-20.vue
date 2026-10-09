<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai8hlzasl.css';
import '../../css/y/y-q9b7fwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ai8hlzasl"/><path class="y-q9b7fwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bed-linen-20" /></template>
