<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyxsmxb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyxsmxb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:colombia-fcf" /></template>
