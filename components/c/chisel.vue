<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbyp43w9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbyp43w9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:chisel" /></template>
