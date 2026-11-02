<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mx7dnqbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx7dnqbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:classify-line" /></template>
