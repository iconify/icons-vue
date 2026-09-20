<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzcl15b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzcl15b6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:brave" /></template>
