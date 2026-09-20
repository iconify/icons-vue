<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptw-w1b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ptw-w1b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:bookmark-plus-fill" /></template>
