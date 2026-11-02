<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apha-ex_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apha-ex_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:code-fill" /></template>
