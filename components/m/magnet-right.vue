<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ah__qkbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ah__qkbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:magnet-right" /></template>
