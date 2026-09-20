<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7_r7vb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j7_r7vb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:baggage-solid" /></template>
