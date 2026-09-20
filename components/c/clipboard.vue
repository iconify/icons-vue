<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfc0hbabl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="yfc0hbabl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:clipboard" /></template>
