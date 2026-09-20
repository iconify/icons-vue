<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o58bh9b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o58bh9b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-send3-filled" /></template>
