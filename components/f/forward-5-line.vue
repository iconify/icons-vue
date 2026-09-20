<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq5f9sn3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq5f9sn3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:forward-5-line" /></template>
