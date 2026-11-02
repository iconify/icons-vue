<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myp4mhcjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myp4mhcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anvil-line" /></template>
