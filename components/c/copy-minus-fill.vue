<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyt617bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyt617bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-minus-fill" /></template>
