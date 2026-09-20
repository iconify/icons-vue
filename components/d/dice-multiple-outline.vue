<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqkr3kbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqkr3kbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dice-multiple-outline" /></template>
