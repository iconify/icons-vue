<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg8g64d4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xg8g64d4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dots-horizontal-circle-fill" /></template>
