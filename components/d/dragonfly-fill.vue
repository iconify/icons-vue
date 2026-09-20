<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngovbnf4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngovbnf4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:dragonfly-fill" /></template>
