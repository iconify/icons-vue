<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5qofebji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5qofebji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-keyboard-caps" /></template>
