<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_1qbpb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s_1qbpb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:alarm-fill" /></template>
