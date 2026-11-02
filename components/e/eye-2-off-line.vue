<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4j21obxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4j21obxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:eye-2-off-line" /></template>
