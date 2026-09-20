<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm7spf6mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm7spf6mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:badge" /></template>
