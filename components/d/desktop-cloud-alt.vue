<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl51nvbub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl51nvbub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:desktop-cloud-alt" /></template>
