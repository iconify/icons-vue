<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3t5d0bra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3t5d0bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:ai-agent" /></template>
