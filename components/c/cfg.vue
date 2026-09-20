<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgf21yb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgf21yb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cfg" /></template>
