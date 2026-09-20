<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g0o9-ebpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="g0o9-ebpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:contrast" /></template>
