<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx8rpcb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx8rpcb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lightning-line" /></template>
