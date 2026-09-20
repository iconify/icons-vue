<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpbttnb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpbttnb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:align-right" /></template>
