<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgdu8pbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgdu8pbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-right-square-filled" /></template>
