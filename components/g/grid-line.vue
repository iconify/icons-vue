<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot6w0-x5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot6w0-x5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:grid-line" /></template>
