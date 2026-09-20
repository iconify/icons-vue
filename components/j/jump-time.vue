<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oodgfcczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oodgfcczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:jump-time" /></template>
