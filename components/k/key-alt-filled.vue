<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpf00ybcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpf00ybcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:key-alt-filled" /></template>
